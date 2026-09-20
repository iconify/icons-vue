<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcwje4bvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:supervisor-account-outline-sharp" /></template>
<style>
.mcwje4bvo {
  fill: currentColor;
  d: path("M15.475 13.025q-.59-.59-.59-1.41q0-.819.59-1.41q.59-.59 1.41-.59q.819 0 1.41.59q.59.591.59 1.41q0 .82-.59 1.41q-.591.59-1.41.59q-.82 0-1.41-.59m-3.09 5.59v-.9q0-.465.232-.843q.232-.379.66-.545q.845-.356 1.748-.534q.904-.177 1.86-.177q.917 0 1.822.177q.905.178 1.785.534q.428.166.66.545q.233.378.233.844v.9zm-4.893-8.107q-.876-.877-.876-2.123t.876-2.123t2.124-.877t2.123.877t.877 2.123t-.877 2.123t-2.123.877t-2.124-.877m-4.876 8.108v-1.647q0-.648.357-1.192q.358-.544.973-.804q1.327-.673 2.756-1.015t2.914-.342q.605 0 1.211.063t1.212.167l-.427.446l-.427.447q-.393-.077-.785-.1t-.784-.023q-1.354 0-2.675.292t-2.518.942q-.327.183-.567.456t-.24.663v.646h6v1zm8.412-8.819q.588-.587.588-1.412t-.588-1.413t-1.412-.587t-1.413.587t-.587 1.413t.587 1.412t1.413.588t1.412-.588");
}

</style>
