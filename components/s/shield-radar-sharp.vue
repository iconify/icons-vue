<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vzpb968gn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shield-radar-sharp" /></template>
<style>
.vzpb968gn {
  fill: currentColor;
  d: path("M17 22q-2.077 0-3.538-1.461T12 17t1.462-3.538T17 12t3.539 1.462T22 17q0 .383-.061.744t-.166.689l-.817-.854q.025-.144.034-.29q.01-.145.01-.289q0-1.65-1.175-2.825T17 13t-2.825 1.175T13 17t1.175 2.825T17 21q.144 0 .29-.01q.144-.01.289-.034l.829.842q-.327.104-.68.153Q17.378 22 17 22m-.99-5.99q.415-.414.99-.414t.99.415t.414.989q0 .075-.133.564l2.671 2.67l-.713.708l-2.666-2.67q-.075.044-.563.132q-.575 0-.99-.414q-.414-.415-.414-.99t.415-.99M5 11.1V5.692l7-2.615l7 2.615v4.216q-.494-.14-.994-.217T17 9.615q-3.08 0-5.233 2.152Q9.616 13.92 9.616 17q0 .867.193 1.704q.193.836.593 1.6q-2.396-1.267-3.899-3.746T5 11.1");
}

</style>
