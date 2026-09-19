<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8jlkgbbp.css';
import '../../css/p/p_mrm8qto.css';
import '../../css/o/oayagp0-d.css';
import '../../css/g/g13jgl9wr.css';
import '../../css/r/rv4dr434i.css';
import '../../css/x/xjl91t_xi.css';
import '../../css/j/j4mjgj17p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i8jlkgbbp"/><path class="p_mrm8qto"/><path class="oayagp0-d"/><path class="g13jgl9wr"/><path class="rv4dr434i"/><path class="xjl91t_xi"/><path class="j4mjgj17p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:no-smoking" /></template>
