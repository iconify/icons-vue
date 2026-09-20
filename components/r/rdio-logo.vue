<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gytqn9b4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gytqn9b4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:rdio-logo" /></template>
