<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xebuqdn9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xebuqdn9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-bottom-fill" /></template>
