<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nctuibqln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nctuibqln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:sign-out-24" /></template>
