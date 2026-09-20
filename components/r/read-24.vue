<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krjlgs_6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krjlgs_6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:read-24" /></template>
