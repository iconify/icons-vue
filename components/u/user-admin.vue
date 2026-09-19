<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9kkqxb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9kkqxb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:user-admin" /></template>
