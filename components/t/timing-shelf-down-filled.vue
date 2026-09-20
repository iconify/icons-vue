<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2euobcyk.css';
import '../../css/r/r78fl8b_u.css';
import '../../css/m/mbmho7ddy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g2euobcyk"/><path class="r78fl8b_u"/><path clip-rule="evenodd" class="mbmho7ddy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:timing-shelf-down-filled" /></template>
