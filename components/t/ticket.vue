<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htbbrjlzo.css';
import '../../css/h/hmqgikzpa.css';
import '../../css/h/howiqgbsw.css';
import '../../css/d/dhkuk8bie.css';
import '../../css/p/p1r_hs_-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="htbbrjlzo"/><path class="hmqgikzpa"/><circle transform="rotate(-44.781 37.124 22.122)" class="howiqgbsw"/><circle transform="rotate(-44.781 43.614 28.661)" class="dhkuk8bie"/><circle transform="rotate(-44.781 50.104 35.2)" class="p1r_hs_-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:ticket" /></template>
