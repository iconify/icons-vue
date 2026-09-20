<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7ahsxa6g.css';
import '../../css/h/h-uptbcqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7ahsxa6g"/><path class="h-uptbcqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:signout-alt" /></template>
