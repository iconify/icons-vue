<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b03zqx2zz.css';
import '../../css/h/h6r-0zwfg.css';
import '../../css/i/iu9qj1lar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b03zqx2zz"/><path class="h6r-0zwfg"/><path class="iu9qj1lar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:role-binding-outlined" /></template>
