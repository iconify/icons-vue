<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp7m51byk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dp7m51byk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-arrows-left-filled" /></template>
