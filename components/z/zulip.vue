<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqnly8k0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iqnly8k0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:zulip" /></template>
