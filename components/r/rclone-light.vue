<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enjks7vil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="enjks7vil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rclone-light" /></template>
