<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_aaqkbpl.css';
import '../../css/u/uzefn3-hw.css';
import '../../css/n/ndep3kwgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="n_aaqkbpl"/><path clip-rule="evenodd" class="uzefn3-hw"/><path clip-rule="evenodd" class="ndep3kwgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-tables-dark" /></template>
