<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrv6k5hte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrv6k5hte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:sifive" /></template>
