<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz7x-rb-m.css';
import '../../css/q/qk8x-bb5p.css';
import '../../css/a/akdxg9upc.css';
import '../../css/m/mz595l-ia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz7x-rb-m"/><path class="qk8x-bb5p"/><path class="akdxg9upc"/><path class="mz595l-ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:volcengine" /></template>
