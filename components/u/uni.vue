<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljj5lbnaa.css';
import '../../css/o/o7a58mbsb.css';
import '../../css/f/fruy1-c_a.css';
import '../../css/y/y_dajcvjj.css';
import '../../css/n/nps6-ccvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ljj5lbnaa"/><path class="o7a58mbsb"/><path class="fruy1-c_a"/><path class="y_dajcvjj"/><path clip-rule="evenodd" class="nps6-ccvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:uni" /></template>
