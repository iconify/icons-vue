<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lskr6z3ls.css';
import '../../css/i/ius8nukxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lskr6z3ls secondary"/><path class="ius8nukxs primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:plane-duo" /></template>
