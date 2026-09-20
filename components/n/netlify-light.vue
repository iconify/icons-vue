<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7y8yu2wv.css';
import '../../css/q/q-8dq0bnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7y8yu2wv"/><path class="q-8dq0bnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:netlify-light" /></template>
