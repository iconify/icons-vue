<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck-mwvbhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck-mwvbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:telescope-fill-24" /></template>
