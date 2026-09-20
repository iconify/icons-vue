<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adnm6ebzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adnm6ebzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:twitch" /></template>
