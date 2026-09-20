<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1_6apbah.css';
import '../../css/d/dnw8ephhm.css';
import '../../css/c/cdkh7bjct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n1_6apbah"/><path class="dnw8ephhm"/><circle class="cdkh7bjct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:map-duotone" /></template>
