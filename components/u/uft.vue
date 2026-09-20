<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="qzkf_acag"/><path class="i1mpixixt"/><path class="z0xc0-2ou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:uft" /></template>
<style>
.bi12bsetm {
  fill: none;
  fill-rule: evenodd;
}

.i1mpixixt {
  fill: var(--svg-color--2b6def, #2b6def);
  d: path("M10.013 5.388h7.493a.703.703 0 0 1 .649.71a.73.73 0 0 1-.125.409l-4.17 7.483h.018l-.687 1.23c-1.125 1.038-.8 2.359.178 2.987l.06.037c.245.146 0 .146.69.373h-9c-.35-.006-.666-.129-.994-.317c-1.053-.603-1.434-1.976-.85-3.065l4.662-8.69a2.17 2.17 0 0 1 2.077-1.157");
}

.qzkf_acag {
  fill: var(--svg-color--2bbdf7, #2bbdf7);
  d: path("M16.658 9.088s.829-.016 3.692 0c.363.021.65.35.65.728a.72.72 0 0 1-.17.466l-1.16 2.063l-.027.052l-2.87 5.117a2.13 2.13 0 0 1-1.811 1.104h-.089l-8.488-.045h-.947v-.017a2.15 2.15 0 0 0 1.63-1.22h.007l4.159-7.449a1.41 1.41 0 0 1 1.261-.798h-.038z");
}

.z0xc0-2ou {
  fill: var(--svg-color--003cb2, #003cb2);
  d: path("M12.553 9.09h4.032l-3.335 6.162c-1.22 2.231.194 3.363 1.619 3.363h-3.471l-.002.003h-5.75a2.13 2.13 0 0 0 1.597-1.052l.04-.071l4.253-7.84a1.36 1.36 0 0 1 1.032-.566z");
}

</style>
