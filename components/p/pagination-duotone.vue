<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hlvk4dsgc.css';
import '../../css/c/cp3aa4bji.css';
import '../../css/k/ks7p16bem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hlvk4dsgc"/><rect class="cp3aa4bji"/><rect class="ks7p16bem"/><rect class="cp3aa4bji"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:pagination-duotone" /></template>
