<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzl5xkfbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dzl5xkfbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:scooter" /></template>
