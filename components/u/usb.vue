<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmlps6b0t.css';
import '../../css/w/wt0pcikiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmlps6b0t"/><path class="wt0pcikiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:usb" /></template>
