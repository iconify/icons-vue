<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smhsy5b9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smhsy5b9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:sound" /></template>
