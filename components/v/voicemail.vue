<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxxb01b_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"top":-6.5};
const content = `<path class="bxxb01b_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:voicemail" /></template>
