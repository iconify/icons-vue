<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/c/cld7pcy1f.css';
import '../../css/m/mnwdukbea.css';
import '../../css/l/l0761sbgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cld7pcy1f"/><path class="mnwdukbea"/><path class="l0761sbgh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mobile-navigator-02" /></template>
