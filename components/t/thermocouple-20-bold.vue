<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc82xxbku.css';
import '../../css/i/im-vrsb-c.css';
import '../../css/a/apexb8rod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rc82xxbku"/><path class="im-vrsb-c"/><path class="apexb8rod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermocouple-20-bold" /></template>
