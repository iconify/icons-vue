<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjmrtsd2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:naphtha" /></template>
<style>
.tjmrtsd2c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.49 1.95q-.021.019-.04.04q-6.7 7.215-6.7 12.51q0 3.003 2.123 5.127T12 21.75t5.127-2.123q2.123-2.124 2.123-5.127q0 .086-.02.17q-.019.084-.057.161q-.038.078-.093.144q-.054.067-.123.119q-3.707 2.852-7.414 0q-2.793-2.148-5.586 0q-.058.046-.124.078q-.067.033-.138.052t-.145.024t-.147-.004q-.073-.01-.143-.034q-.07-.023-.134-.06t-.12-.086q-.055-.048-.1-.107q-.076-.098-.116-.215q-.04-.118-.04-.242q0-.086.02-.17q.019-.084.057-.161q.038-.078.093-.144q.054-.067.123-.119q3.707-2.852 7.414 0q2.793 2.148 5.586 0q.118-.091.262-.13t.292-.02t.277.094t.22.193q.076.098.116.215q.04.118.04.242q0-5.295-6.7-12.51q-.102-.11-.238-.172q-.135-.062-.284-.067t-.289.046t-.249.153");
}

</style>
