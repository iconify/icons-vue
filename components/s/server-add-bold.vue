<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c37kw4biu.css';
import '../../css/n/nr6yb3djc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c37kw4biu"/><path class="nr6yb3djc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:server-add-bold" /></template>
