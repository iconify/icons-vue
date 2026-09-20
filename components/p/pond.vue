<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="gc95uq-ne"/><path class="zag005qed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pond" /></template>
<style>
.bi12bsetm {
  fill: none;
  fill-rule: evenodd;
}

.gc95uq-ne {
  fill: var(--svg-color--2db8e3, #2db8e3);
  d: path("M14.64 6.356A1.22 1.22 0 0 0 13.777 6h-.003a1.22 1.22 0 0 0-.864.36l-9.552 9.56a1.21 1.21 0 0 0 .004 1.725a1.2 1.2 0 0 0 .863.356c.328 0 .637-.128.869-.36l9.551-9.56a1.22 1.22 0 0 0-.003-1.725");
}

.zag005qed {
  fill: var(--svg-color--3840c7, #3840c7);
  d: path("M20.241 6.093a1.23 1.23 0 0 0-1.34.267l-9.583 9.56c-.23.23-.32.54-.318.864c0 .323.092.633.323.861a1.235 1.235 0 0 0 1.737-.005l7.44-7.465v6.606c0 .323.173.633.403.862a1.234 1.234 0 0 0 1.737 0c.23-.229.36-.539.36-.862V7.22c0-.242-.071-.478-.206-.679a1.2 1.2 0 0 0-.553-.449");
}

</style>
