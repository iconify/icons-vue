<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxpyef0hm.css';
import '../../css/e/ext4fquee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxpyef0hm"/><path class="ext4fquee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:school-filled" /></template>
