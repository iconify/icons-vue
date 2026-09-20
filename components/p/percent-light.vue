<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/c/cidikfavb.css';
import '../../css/x/xn6ppk3eg.css';
import '../../css/x/xg67yobqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="cidikfavb"/><circle class="xn6ppk3eg"/><circle class="xg67yobqd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:percent-light" /></template>
