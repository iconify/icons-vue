<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcxqr3faj.css';
import '../../css/u/ud305ub0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tcxqr3faj"/><path class="ud305ub0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:newspaper-ltr" /></template>
