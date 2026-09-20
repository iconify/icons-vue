<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/glsnqibje.css';
import '../../css/b/b6ykzlr9k.css';
import '../../css/f/fhf7djstr.css';
import '../../css/y/yod4tl2uo.css';
import '../../css/t/t4adpsbdt.css';
import '../../css/p/pr1jznbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="glsnqibje"/><path class="b6ykzlr9k"/><path class="fhf7djstr"/><path class="yod4tl2uo"/><path class="t4adpsbdt"/><path class="pr1jznbmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sleeping-square-broken" /></template>
