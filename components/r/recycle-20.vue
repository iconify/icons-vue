<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzxqjgbju.css';
import '../../css/o/ozlm6mbor.css';
import '../../css/b/b649fkhgn.css';
import '../../css/g/g8h37j62m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yzxqjgbju"/><path class="ozlm6mbor"/><path class="b649fkhgn"/><path class="g8h37j62m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:recycle-20" /></template>
