<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_wke9bko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_wke9bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:skype-alt" /></template>
