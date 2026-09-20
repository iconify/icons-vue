<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y70-_76-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y70-_76-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:password-check-filled" /></template>
