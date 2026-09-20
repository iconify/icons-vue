<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1im-i5ss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1im-i5ss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:rectangle-vertical-solid" /></template>
