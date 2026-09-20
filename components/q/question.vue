<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vskh41bae.css';
import '../../css/y/y_g1oe_0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vskh41bae"/><path class="y_g1oe_0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:question" /></template>
