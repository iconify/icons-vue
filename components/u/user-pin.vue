<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a52c-wxdw.css';
import '../../css/l/lgn49_byf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a52c-wxdw"/><path class="lgn49_byf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:user-pin" /></template>
