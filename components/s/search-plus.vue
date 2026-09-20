<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9v4b39in.css';
import '../../css/x/x8-usg97v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path class="c9v4b39in"/><path clip-rule="evenodd" class="x8-usg97v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:search-plus" /></template>
