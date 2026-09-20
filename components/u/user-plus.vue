<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf4a-abip.css';
import '../../css/b/b45rmqb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf4a-abip"/><path class="b45rmqb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:user-plus" /></template>
