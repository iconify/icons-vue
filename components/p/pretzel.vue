<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iblxv-boo.css';
import '../../css/t/twg1_zbxj.css';
import '../../css/e/ex20ps24v.css';
import '../../css/b/brzn_0bpr.css';
import '../../css/k/k0d8hdbwy.css';
import '../../css/y/y4ij6tyga.css';
import '../../css/y/y_-_q-u8u.css';
import '../../css/a/aa_6q9b9u.css';
import '../../css/j/jj_-k1_mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<ellipse class="iblxv-boo"/><path class="twg1_zbxj"/><path class="ex20ps24v"/><g class="brzn_0bpr"><path class="k0d8hdbwy"/><path class="y4ij6tyga"/><path class="y_-_q-u8u"/><path class="aa_6q9b9u"/><path class="jj_-k1_mh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:pretzel" /></template>
