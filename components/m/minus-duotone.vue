<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt83wcb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt83wcb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:minus-duotone" /></template>
