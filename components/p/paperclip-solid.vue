<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glkby61tt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glkby61tt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:paperclip-solid" /></template>
