<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkwaezb_n.css';
import '../../css/o/oj7j_1bgn.css';
import '../../css/s/ss3h7jkmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkwaezb_n wm-shadow"/><path class="oj7j_1bgn wm-k"/><path class="ss3h7jkmy wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:rotate-cw" /></template>
