<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/beaf8k8ky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="beaf8k8ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:smiley-happy-bold" /></template>
