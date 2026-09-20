<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw4toyb6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw4toyb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:zulip" /></template>
