<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w82hbqbbx.css';
import '../../css/v/v4i2ew1ke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w82hbqbbx"/><circle class="v4i2ew1ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:setting-alt-line-duotone" /></template>
