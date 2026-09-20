<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw93vibwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw93vibwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:screw-machine-flat-top" /></template>
