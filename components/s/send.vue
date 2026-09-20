<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srbp6jbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="srbp6jbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:send" /></template>
