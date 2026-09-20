<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjiz8hbrl.css';
import '../../css/h/hana-fm8g.css';
import '../../css/w/w6h6ugqaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjiz8hbrl"/><circle class="hana-fm8g"/><path clip-rule="evenodd" class="w6h6ugqaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:user-box-duotone" /></template>
