<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygb5ynbry.css';
import '../../css/v/v4qkmnlcy.css';
import '../../css/a/a-vs3_0vm.css';
import '../../css/z/zcnczmjty.css';
import '../../css/z/zh8221lvv.css';
import '../../css/g/gapgxrbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygb5ynbry"/><path class="v4qkmnlcy"/><path class="a-vs3_0vm"/><path class="zcnczmjty"/><path class="zh8221lvv"/><path class="gapgxrbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:share-circle-bold" /></template>
