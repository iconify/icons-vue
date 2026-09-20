<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b84ui104o.css';
import '../../css/w/wcbu4acoh.css';
import '../../css/y/y--cdmb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="b84ui104o"/><path class="wcbu4acoh"/><path class="y--cdmb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:ultrasound" /></template>
