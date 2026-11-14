<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbd8gyb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:neptune-planet" /></template>
<style>
.cbd8gyb3u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.5 12.001q-.001 3.935 2.781 6.718T12 21.503t6.719-2.784Q21.501 15.936 21.5 12q.001-3.936-2.781-6.719T12 2.497q-3.936 0-6.719 2.784Q2.499 8.064 2.5 11.999q0-.086.02-.17q.019-.084.057-.161t.093-.143t.123-.119q4.653-3.58 9.643-.016q2.429 1.735 4.033 1.735q1.588 0 3.824-1.719q.118-.091.262-.13t.292-.02t.277.094t.22.193q.076.098.116.215q.04.118.04.242q0 .086-.019.17q-.02.084-.058.161q-.038.078-.093.144q-.054.067-.123.119q-4.653 3.58-9.643.016q-2.429-1.735-4.033-1.735q-1.588 0-3.824 1.719q-.058.046-.124.078q-.067.033-.138.052t-.145.024t-.147-.004q-.073-.01-.143-.034q-.07-.023-.134-.06t-.12-.086t-.1-.107q-.076-.098-.116-.215t-.04-.241");
}

</style>
