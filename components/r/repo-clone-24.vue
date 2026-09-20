<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw6bhtqns.css';
import '../../css/s/sfw4e80bn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw6bhtqns"/><path class="sfw4e80bn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:repo-clone-24" /></template>
