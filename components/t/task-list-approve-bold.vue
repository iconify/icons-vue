<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnvdesbnf.css';
import '../../css/u/ur9gklu2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnvdesbnf"/><path class="ur9gklu2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:task-list-approve-bold" /></template>
