<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v02mowbow.css';
import '../../css/c/c2nbybb8g.css';
import '../../css/x/xj22oqcto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v02mowbow"/><circle class="c2nbybb8g"/><rect class="xj22oqcto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:rsshub" /></template>
