<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz27u516v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tz27u516v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:scan-user-fill" /></template>
