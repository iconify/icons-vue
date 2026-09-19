<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuuzlabau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="fuuzlabau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:public-address-loudspeaker-small" /></template>
