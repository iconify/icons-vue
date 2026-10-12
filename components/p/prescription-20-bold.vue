<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iccsyvk3j.css';
import '../../css/o/otxs-bbsk.css';
import '../../css/k/kbn91fbuc.css';
import '../../css/y/ymlf35b1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iccsyvk3j"/><path class="otxs-bbsk"/><path class="kbn91fbuc"/><path class="ymlf35b1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:prescription-20-bold" /></template>
