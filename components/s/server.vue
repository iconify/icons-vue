<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/afpdohbzp.css';
import '../../css/l/l8psdub6q.css';
import '../../css/z/zalithk9q.css';
import '../../css/e/edpqa5b5n.css';
import '../../css/o/ovcld-b7h.css';
import '../../css/p/pnfa4vatg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><rect class="afpdohbzp"/><circle class="l8psdub6q"/><circle class="zalithk9q"/><rect class="edpqa5b5n"/><circle class="ovcld-b7h"/><circle class="pnfa4vatg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:server" /></template>
