<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzn8lfy8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzn8lfy8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:navigation" /></template>
