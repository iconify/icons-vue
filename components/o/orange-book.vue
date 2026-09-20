<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8a-spftx.css';
import '../../css/f/f--a68y4g.css';
import '../../css/g/g-vas9vud.css';
import '../../css/o/ogbi9fbdn.css';
import '../../css/a/ay8131wny.css';
import '../../css/p/pvt39jcep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="a8a-spftx"/><path class="f--a68y4g"/><path class="g-vas9vud"/><path class="ogbi9fbdn"/><circle class="ay8131wny"/><path class="pvt39jcep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:orange-book" /></template>
