<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhafzrngg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":300};
const content = `<path class="yhafzrngg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:semantic-release-light" /></template>
