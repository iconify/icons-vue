<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5xdmn.css';
import '../../css/i/izvovy.css';
import '../../css/z/zxndow.css';
import '../../css/f/f-8s9h.css';
import '../../css/g/grlnmu.css';
import '../../css/y/yl0nmc.css';
import '../../css/b/botfzx.css';
import '../../css/f/f59n3y.css';
import '../../css/s/so-from-22.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGdzvYAcqY"><path class="c5xdmn izvovy zxndow"/><path class="c5xdmn f-8s9h zxndow"/><path class="c5xdmn grlnmu yl0nmc"/></mask></defs><path mask="url(#SVGdzvYAcqY)" class="botfzx"/><path class="c5xdmn f59n3y yl0nmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:person-off" /></template>
