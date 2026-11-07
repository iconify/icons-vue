<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf34h9jbx.css';
import '../../css/y/ypo27hbxa.css';
import '../../css/k/kfd5w9qxs.css';
import '../../css/y/yyc8v2bch.css';
import '../../css/w/w3n7fxbuc.css';
import '../../css/r/rmy-f-bvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gf34h9jbx"/><path class="ypo27hbxa"/><path class="kfd5w9qxs"/><path class="yyc8v2bch"/><path class="w3n7fxbuc"/><path clip-rule="evenodd" class="rmy-f-bvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rocket-2-outline" /></template>
