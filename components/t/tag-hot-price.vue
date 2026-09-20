<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/s/sd5_95y7u.css';
import '../../css/w/wqbd_ktkq.css';
import '../../css/s/svb95kb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="sd5_95y7u"/><path class="wqbd_ktkq"/><path class="svb95kb8y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:tag-hot-price" /></template>
