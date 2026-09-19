<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iimgyyl1w.css';
import '../../css/d/dta0--2ub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iimgyyl1w"/><path clip-rule="evenodd" class="dta0--2ub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:mouse-alt-outline" /></template>
