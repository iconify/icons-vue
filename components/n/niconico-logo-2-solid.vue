<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2g16ob1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o2g16ob1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:niconico-logo-2-solid" /></template>
