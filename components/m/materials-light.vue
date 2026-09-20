<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to-5kdesz.css';
import '../../css/g/g-o3_4ixm.css';
import '../../css/t/tvs0_y9tl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="to-5kdesz"><path class="g-o3_4ixm"/><path class="tvs0_y9tl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:materials-light" /></template>
