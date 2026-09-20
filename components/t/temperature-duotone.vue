<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iaqdor5_y.css';
import '../../css/i/i9270-aoh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iaqdor5_y"/><path class="i9270-aoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:temperature-duotone" /></template>
