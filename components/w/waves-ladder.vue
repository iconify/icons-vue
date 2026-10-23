<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1ybz-kxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1ybz-kxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:waves-ladder" /></template>
