<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wflyv4bxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wflyv4bxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:relation-one-or-many-to-only-one" /></template>
