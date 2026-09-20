<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmoiotb8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmoiotb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:shield-lock-24" /></template>
