<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agnf6sbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agnf6sbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:screenmirroring-filled" /></template>
