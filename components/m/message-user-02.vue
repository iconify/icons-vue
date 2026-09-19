<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/k/k9drbtbgy.css';
import '../../css/l/lgzyerhxp.css';
import '../../css/c/c8z83bd8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k9drbtbgy"/><path class="lgzyerhxp"/><path class="c8z83bd8p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:message-user-02" /></template>
