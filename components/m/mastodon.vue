<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzr0uqbuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dzr0uqbuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:mastodon" /></template>
