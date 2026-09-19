<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxjfcsudw.css';
import '../../css/q/q-qy_1ldb.css';
import '../../css/v/v0mgkb00e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xxjfcsudw"/><path class="q-qy_1ldb"/><path class="v0mgkb00e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:typeorm-wordmark" /></template>
