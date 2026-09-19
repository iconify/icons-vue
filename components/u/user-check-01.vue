<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/e/e41hsswqv.css';
import '../../css/z/zx2_eugjs.css';
import '../../css/g/gahfb5buq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e41hsswqv"/><circle class="zx2_eugjs"/><path class="gahfb5buq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:user-check-01" /></template>
