<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h32t530tv.css';
import '../../css/n/n9cednr3v.css';
import '../../css/u/u5jnbt9yj.css';
import '../../css/h/hftaky--n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h32t530tv"/><path class="n9cednr3v"/><path class="u5jnbt9yj"/><path class="hftaky--n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:neutral" /></template>
