<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f657yvg-i.css';
import '../../css/f/f--rpx6kf.css';
import '../../css/i/i2wvy_wgy.css';
import '../../css/r/r4hn0mbcy.css';
import '../../css/x/x8poo_bjf.css';
import '../../css/d/de0_phkht.css';
import '../../css/r/r2xtw7bor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="f657yvg-i"/><g class="f--rpx6kf"><circle class="i2wvy_wgy"/><path class="r4hn0mbcy"/></g><g class="x8poo_bjf"><circle class="i2wvy_wgy"/><path class="de0_phkht"/><path class="r2xtw7bor"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:person-surfing-medium-skin-tone" /></template>
