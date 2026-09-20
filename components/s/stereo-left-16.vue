<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv1c6chiz.css';
import '../../css/y/y471xbw7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kv1c6chiz"/><path clip-rule="evenodd" class="y471xbw7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:stereo-left-16" /></template>
