<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyp8s5b_x.css';
import '../../css/i/im7csbc2a.css';
import '../../css/z/zqzklisui.css';
import '../../css/p/pkj7clbju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vyp8s5b_x"/><path class="im7csbc2a"/><path class="zqzklisui"/><path class="pkj7clbju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-irradiance-48" /></template>
