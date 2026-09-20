<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss8-hublk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ss8-hublk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:remove-column" /></template>
