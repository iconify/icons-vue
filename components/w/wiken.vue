<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akgok5bfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akgok5bfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:wiken" /></template>
