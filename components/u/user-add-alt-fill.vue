<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i-kbc2bzf.css';
import '../../css/l/l4ki6lbzu.css';
import '../../css/n/nkz6axb6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="i-kbc2bzf"/><path class="l4ki6lbzu"/><path class="nkz6axb6t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:user-add-alt-fill" /></template>
