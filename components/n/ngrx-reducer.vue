<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2e0vabgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":300};
const content = `<path class="q2e0vabgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:ngrx-reducer" /></template>
