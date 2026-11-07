<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqt3vmb-u.css';
import '../../css/j/jjt0fksdh.css';
import '../../css/o/om59irbzs.css';
import '../../css/k/k62rgabws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqt3vmb-u"/><path class="jjt0fksdh"/><path class="om59irbzs"/><path class="k62rgabws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:password-minimalistic-input-bold-duotone" /></template>
