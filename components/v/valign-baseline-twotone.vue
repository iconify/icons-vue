<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljvi6y.css';
import '../../css/s/s1ui7u.css';
import '../../css/x/xb-a0u.css';
import '../../css/s/so-from-22.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-to-0.css';
import '../../css/f/fill-to-0_3.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljvi6y s1ui7u"/><path class="s1ui7u xb-a0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:valign-baseline-twotone" /></template>
