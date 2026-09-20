<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s88m1dw2h.css';
import '../../css/r/rymzj_w6f.css';
import '../../css/h/hzqb1s7ax.css';
import '../../css/c/cothx-xat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s88m1dw2h"/><path class="rymzj_w6f"/><path class="hzqb1s7ax"/><path class="cothx-xat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:user-arrows" /></template>
