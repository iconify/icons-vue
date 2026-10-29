<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s20yxy53u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s20yxy53u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:message-square" /></template>
