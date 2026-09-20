<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3qp6x1gw.css';
import '../../css/c/cg710qboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3qp6x1gw"/><path class="cg710qboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:play-duotone" /></template>
