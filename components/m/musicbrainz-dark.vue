<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2wdzqbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f2wdzqbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:musicbrainz-dark" /></template>
