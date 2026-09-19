<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc--wpv5i.css';
import '../../css/q/q5kv900nb.css';
import '../../css/v/vntad-bds.css';
import '../../css/s/sc8gq5b4w.css';
import '../../css/u/uuauku1pl.css';
import '../../css/q/qkce8ac2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<defs><radialGradient id="SVGSJNuYcoU" cx="0" cy="0" r="1" gradientTransform="matrix(10.5875 0 0 10.784 4.993 -.868)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1"/></radialGradient></defs><path class="q5kv900nb"/><path fill="url(#SVGSJNuYcoU)" class="vntad-bds"/><path class="sc8gq5b4w"/><path class="uuauku1pl"/><path class="qkce8ac2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:poetry-lock" /></template>
