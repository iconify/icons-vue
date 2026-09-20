<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu7_b03hk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hu7_b03hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:usergroup-filled" /></template>
