<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyfsfosee.css';
import '../../css/g/giof89hnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyfsfosee"/><path clip-rule="evenodd" class="giof89hnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:social-whatsapp" /></template>
