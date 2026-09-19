<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agr3pubbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agr3pubbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:video-camera" /></template>
