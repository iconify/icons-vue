<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dn-rk_b9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dn-rk_b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sidebar2-filled" /></template>
