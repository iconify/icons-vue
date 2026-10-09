<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bepxe4bel.css';
import '../../css/j/j7sm7rbxk.css';
import '../../css/s/sai8ik0bu.css';
import '../../css/w/w-imt2b_l.css';
import '../../css/p/pp6ycgbmp.css';
import '../../css/i/itt8lj0lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bepxe4bel"/><path class="j7sm7rbxk"/><path class="sai8ik0bu"/><path class="w-imt2b_l"/><path class="pp6ycgbmp"/><path class="itt8lj0lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-turbine-20-bold" /></template>
