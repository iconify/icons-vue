<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/h/hzq80o3qy.css';
import '../../css/r/r97-bnbcb.css';
import '../../css/z/zfyjy16gh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="hzq80o3qy"/><path class="r97-bnbcb"/><path class="zfyjy16gh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:phone-shield-flat" /></template>
