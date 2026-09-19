<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obfizfrne.css';
import '../../css/k/keee5eb3m.css';
import '../../css/m/m_084tbji.css';
import '../../css/f/fth49-b6s.css';
import '../../css/h/hjn6x0bvp.css';
import '../../css/v/vj46e_87r.css';
import '../../css/h/h2qrtnbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obfizfrne"/><circle class="keee5eb3m"/><circle class="m_084tbji"/><path class="fth49-b6s"/><circle class="hjn6x0bvp"/><circle class="vj46e_87r"/><path class="h2qrtnbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:server" /></template>
