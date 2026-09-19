<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muf9dmvup.css';
import '../../css/t/ta5vg_czn.css';
import '../../css/x/xbh5ctbef.css';
import '../../css/p/pvabr9frm.css';
import '../../css/b/b5rkaq6ql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="muf9dmvup"/><path class="ta5vg_czn"/><path class="xbh5ctbef"/><path class="pvabr9frm"/><path class="b5rkaq6ql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:terraform-wordmark" /></template>
