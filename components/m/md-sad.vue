<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo_qwjrtd.css';
import '../../css/a/ad6uu_b7l.css';
import '../../css/z/zp0o_6cpw.css';
import '../../css/d/dj5hahi0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oo_qwjrtd"/><path class="ad6uu_b7l"/><path class="zp0o_6cpw"/><path class="dj5hahi0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-sad" /></template>
