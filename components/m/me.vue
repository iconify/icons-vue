<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/z/zds4z092f.css';
import '../../css/t/tsphmabow.css';
import '../../css/d/dr7owxbgw.css';
import '../../css/r/r19r8o3en.css';
import '../../css/d/dgv5akv2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="zds4z092f"/><path class="tsphmabow"/><path class="dr7owxbgw"/><path class="r19r8o3en"/><path class="dgv5akv2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:me" /></template>
