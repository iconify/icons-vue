<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2znqy5bg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2znqy5bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:tado" /></template>
