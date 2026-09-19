<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg3a7lbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tg3a7lbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:tumblr" /></template>
